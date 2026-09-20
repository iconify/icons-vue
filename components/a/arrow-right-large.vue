<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6nnl5bwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6nnl5bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-right-large" /></template>
