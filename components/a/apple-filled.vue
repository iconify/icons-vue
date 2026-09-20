<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcq4ndq-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcq4ndq-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:apple-filled" /></template>
