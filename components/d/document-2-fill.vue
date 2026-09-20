<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kifu49xfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kifu49xfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:document-2-fill" /></template>
