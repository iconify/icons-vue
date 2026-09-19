<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxh1f2bbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="uxh1f2bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-up-9-1" /></template>
