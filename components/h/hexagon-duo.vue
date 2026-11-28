<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tryzyvb9o.css';
import '../../css/k/kftm6xogs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary tryzyvb9o"/><path class="kftm6xogs primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hexagon-duo" /></template>
