<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtwyabb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mtwyabb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hand-card-fill" /></template>
