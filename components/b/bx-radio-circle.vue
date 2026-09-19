<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boeyg5zgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="boeyg5zgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-radio-circle" /></template>
