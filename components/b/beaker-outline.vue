<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv5ugxbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hv5ugxbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:beaker-outline" /></template>
