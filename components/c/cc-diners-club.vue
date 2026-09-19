<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm5x-vbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="xm5x-vbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:cc-diners-club" /></template>
