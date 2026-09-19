<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_x_tgb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="t_x_tgb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:bulma" /></template>
