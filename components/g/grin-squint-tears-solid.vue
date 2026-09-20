<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0v2cdcqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z0v2cdcqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:grin-squint-tears-solid" /></template>
