<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl8frbc0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sl8frbc0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:broccoli-filled" /></template>
