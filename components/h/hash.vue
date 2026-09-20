<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q320efsbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q320efsbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:hash" /></template>
