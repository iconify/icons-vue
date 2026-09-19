<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwvda6otg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwvda6otg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-file-export" /></template>
