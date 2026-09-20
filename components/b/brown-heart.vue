<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4yp20btu.css';
import '../../css/t/tqz5znvkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="m4yp20btu"/><path class="tqz5znvkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:brown-heart" /></template>
