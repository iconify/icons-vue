<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve6u0vqil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve6u0vqil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-double-right" /></template>
