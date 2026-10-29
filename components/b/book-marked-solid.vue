<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcbtwlbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcbtwlbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:book-marked-solid" /></template>
