<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssr9qfzls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="ssr9qfzls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:accounts-list" /></template>
