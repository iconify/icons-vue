<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcpx__fvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcpx__fvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:category-filled" /></template>
