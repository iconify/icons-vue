<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrh4tzs5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="qrh4tzs5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:lira-sign" /></template>
