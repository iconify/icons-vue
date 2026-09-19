<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4lr5punx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="a4lr5punx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:address-card" /></template>
