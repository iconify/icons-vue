<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exyoo0b5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="exyoo0b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-stack-outline" /></template>
