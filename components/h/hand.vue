<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsb_k_b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsb_k_b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:hand" /></template>
