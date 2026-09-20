<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf-iosbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mf-iosbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:happy-face-in-circle-outline" /></template>
