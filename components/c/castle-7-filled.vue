<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybk7p_byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybk7p_byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:castle-7-filled" /></template>
