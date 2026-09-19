<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m496c9reb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m496c9reb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bong-filled" /></template>
