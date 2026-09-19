<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in_uieb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="in_uieb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-up-short-wide" /></template>
