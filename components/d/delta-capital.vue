<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy3z-7b_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy3z-7b_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:delta-capital" /></template>
