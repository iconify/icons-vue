<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhc7zgogx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1408};
const content = `<path class="qhc7zgogx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:folder-o" /></template>
