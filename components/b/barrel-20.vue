<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs4nodbts.css';
import '../../css/g/gy2cg1ook.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xs4nodbts"/><path class="gy2cg1ook"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:barrel-20" /></template>
