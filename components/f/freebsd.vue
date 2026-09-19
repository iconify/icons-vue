<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkonw9bfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="xkonw9bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:freebsd" /></template>
