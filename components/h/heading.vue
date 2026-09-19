<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsv_vsx-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hsv_vsx-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:heading" /></template>
