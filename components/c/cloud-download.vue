<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e29ch1r5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e29ch1r5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:cloud-download" /></template>
