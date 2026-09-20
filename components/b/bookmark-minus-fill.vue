<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c88y4sg0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c88y4sg0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:bookmark-minus-fill" /></template>
