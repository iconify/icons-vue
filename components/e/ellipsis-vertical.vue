<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej74ic_ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej74ic_ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:ellipsis-vertical" /></template>
