<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6rbxzurq.css';
import '../../css/v/vvznrfbcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6rbxzurq"/><path class="vvznrfbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mail-dot-filled" /></template>
