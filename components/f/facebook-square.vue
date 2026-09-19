<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl24r7i0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="wl24r7i0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:facebook-square" /></template>
