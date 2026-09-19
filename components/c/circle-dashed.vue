<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q12d-8xco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q12d-8xco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:circle-dashed" /></template>
