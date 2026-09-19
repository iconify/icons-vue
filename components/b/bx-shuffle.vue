<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk9fdi05w.css';
import '../../css/e/exaqnd3xk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk9fdi05w"/><path class="exaqnd3xk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-shuffle" /></template>
