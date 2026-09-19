<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y30k_otqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y30k_otqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:fast-forward" /></template>
