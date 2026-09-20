<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc82nbjiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gc82nbjiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:grid-lock-filled" /></template>
