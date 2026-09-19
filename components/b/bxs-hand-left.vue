<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0taubxor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0taubxor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-hand-left" /></template>
