<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aio2xbbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aio2xbbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-builder-light" /></template>
