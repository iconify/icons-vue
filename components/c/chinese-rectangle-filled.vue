<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxozi2b1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxozi2b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chinese-rectangle-filled" /></template>
