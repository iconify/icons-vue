<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj4fp2z8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sj4fp2z8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:atom" /></template>
