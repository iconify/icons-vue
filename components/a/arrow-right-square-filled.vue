<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1y-5hb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1y-5hb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-right-square-filled" /></template>
