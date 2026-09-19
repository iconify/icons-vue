<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw8gfzvcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sw8gfzvcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:cloud-error-fill" /></template>
