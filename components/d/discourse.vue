<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy-ihumxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="iy-ihumxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:discourse" /></template>
