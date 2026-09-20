<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dipa96bei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dipa96bei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:clear-formatting-filled" /></template>
