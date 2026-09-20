<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1ro-p46f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1ro-p46f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:focus-fill" /></template>
