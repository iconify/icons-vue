<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v97a6o29o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v97a6o29o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:laravel" /></template>
