<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdure-b1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdure-b1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-home-alt-2" /></template>
