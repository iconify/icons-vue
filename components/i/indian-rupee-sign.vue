<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akr445bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="akr445bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:indian-rupee-sign" /></template>
