<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmq6uom3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmq6uom3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-wide-line" /></template>
