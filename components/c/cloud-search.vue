<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed_o99bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ed_o99bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-search" /></template>
