<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq4vm8b0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sq4vm8b0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:double-alt-arrow-right-outline" /></template>
