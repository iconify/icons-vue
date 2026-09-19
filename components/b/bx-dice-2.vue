<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c98at3bul.css';
import '../../css/g/gxcn5z-fm.css';
import '../../css/y/y90j6oboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c98at3bul"/><circle class="gxcn5z-fm"/><circle class="y90j6oboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-dice-2" /></template>
