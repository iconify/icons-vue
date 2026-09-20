<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv99bxbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv99bxbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:lock-unlocked" /></template>
