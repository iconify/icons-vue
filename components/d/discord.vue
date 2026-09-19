<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tym80lb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="tym80lb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:discord" /></template>
