<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-e-5bb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-e-5bb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:crown" /></template>
