<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoh5rg3zj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uoh5rg3zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:folder-video" /></template>
