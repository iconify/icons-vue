<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqn5az9ja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqn5az9ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:gender-female" /></template>
