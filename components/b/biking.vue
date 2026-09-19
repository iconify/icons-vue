<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1g9gabpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="h1g9gabpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:biking" /></template>
