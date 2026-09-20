<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgdo9jz0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgdo9jz0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:gender-male" /></template>
