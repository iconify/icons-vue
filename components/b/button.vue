<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzc1k193u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzc1k193u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:button" /></template>
