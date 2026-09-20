<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9-_sbbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9-_sbbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:gmm" /></template>
