<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7t3-hb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7t3-hb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:image-filled" /></template>
