<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsq3reb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="xsq3reb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:behance-square" /></template>
