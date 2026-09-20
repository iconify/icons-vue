<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y74nljbre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y74nljbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:layouts-right" /></template>
