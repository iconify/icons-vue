<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o289ctp6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o289ctp6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-file-txt" /></template>
