<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbnccbbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbnccbbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:betalist-logo" /></template>
