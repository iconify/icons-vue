<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx2_3irej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zx2_3irej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:airbuds-left-outline" /></template>
