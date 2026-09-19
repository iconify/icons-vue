<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4-6_2nty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4-6_2nty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-to-top-filled" /></template>
