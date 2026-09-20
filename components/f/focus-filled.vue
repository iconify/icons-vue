<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk7o3vb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk7o3vb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:focus-filled" /></template>
