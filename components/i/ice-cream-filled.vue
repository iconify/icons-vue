<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmqdgf2hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmqdgf2hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ice-cream-filled" /></template>
