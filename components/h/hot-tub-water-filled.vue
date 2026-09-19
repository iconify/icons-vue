<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6b4f9b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6b4f9b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:hot-tub-water-filled" /></template>
