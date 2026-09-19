<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r15cen0uv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r15cen0uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-down-circle-solid" /></template>
