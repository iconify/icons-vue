<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vik2i1kjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vik2i1kjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:keyboard-asterisk-2" /></template>
