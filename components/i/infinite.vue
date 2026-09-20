<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsyc3nk8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-6.5};
const content = `<path class="vsyc3nk8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:infinite" /></template>
