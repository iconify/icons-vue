<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqrkjk4za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="eqrkjk4za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:eye-closed" /></template>
