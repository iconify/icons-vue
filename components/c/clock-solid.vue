<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lji_g4btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lji_g4btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:clock-solid" /></template>
