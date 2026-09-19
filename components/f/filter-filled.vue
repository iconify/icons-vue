<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhor8i0dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhor8i0dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:filter-filled" /></template>
