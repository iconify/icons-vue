<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c98at3bul.css';
import '../../css/t/t6wz8cb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c98at3bul"/><circle class="t6wz8cb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-dice-1" /></template>
