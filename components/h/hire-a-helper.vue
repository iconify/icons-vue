<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m46zd30nf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m46zd30nf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hire-a-helper" /></template>
