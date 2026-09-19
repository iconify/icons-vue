<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r11i6spuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r11i6spuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:car" /></template>
