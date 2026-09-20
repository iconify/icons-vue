<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjgqvdb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mjgqvdb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:layouts-content" /></template>
