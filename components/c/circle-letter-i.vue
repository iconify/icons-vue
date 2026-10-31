<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re3s7de2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re3s7de2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:circle-letter-i" /></template>
