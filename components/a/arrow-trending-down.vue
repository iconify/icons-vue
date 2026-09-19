<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycocobchx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycocobchx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-trending-down" /></template>
