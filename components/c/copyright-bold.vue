<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zma2bx9-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zma2bx9-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:copyright-bold" /></template>
