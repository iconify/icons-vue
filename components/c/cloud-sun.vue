<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfdat4jsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="zfdat4jsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:cloud-sun" /></template>
