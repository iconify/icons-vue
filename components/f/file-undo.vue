<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dydocybmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dydocybmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-undo" /></template>
