<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uong3y8dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uong3y8dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:envelope-redo" /></template>
