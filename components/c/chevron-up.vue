<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m63-p253l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="m63-p253l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:chevron-up" /></template>
