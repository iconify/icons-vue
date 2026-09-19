<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9f01_r4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j9f01_r4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:hand-rock" /></template>
