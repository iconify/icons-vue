<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4x0p8byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4x0p8byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:expand-left" /></template>
