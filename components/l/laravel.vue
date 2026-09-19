<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5vd25u4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":35,"height":24};
const content = `<path class="u5vd25u4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:laravel" /></template>
