<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxca7_wsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxca7_wsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-store" /></template>
