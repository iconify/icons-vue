<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt5bmx3ap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zt5bmx3ap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:cloud" /></template>
