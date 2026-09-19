<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfyrcmbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfyrcmbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:diamond-filled" /></template>
