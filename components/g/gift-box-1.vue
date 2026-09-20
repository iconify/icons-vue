<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmg79ybge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmg79ybge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:gift-box-1" /></template>
