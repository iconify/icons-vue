<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3kb7_czp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="k3kb7_czp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:align-right" /></template>
