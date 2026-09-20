<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy32t8f8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy32t8f8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:game-developer" /></template>
