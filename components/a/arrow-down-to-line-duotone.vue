<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2pk00b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2pk00b7t primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-down-to-line-duotone" /></template>
