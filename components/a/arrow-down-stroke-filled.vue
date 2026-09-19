<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awuzu-b2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awuzu-b2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-down-stroke-filled" /></template>
