<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/typ-1_bel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="typ-1_bel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:gender-male-female" /></template>
