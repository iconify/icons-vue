<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty1qptbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":280,"height":384};
const content = `<path class="ty1qptbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:audio" /></template>
