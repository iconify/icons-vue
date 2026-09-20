<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf6_ihbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="bf6_ihbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:align-text-center" /></template>
