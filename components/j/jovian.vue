<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiyclc4dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qiyclc4dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:jovian" /></template>
