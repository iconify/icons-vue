<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yanv2cchx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yanv2cchx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:chevron-double-up" /></template>
