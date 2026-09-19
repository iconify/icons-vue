<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r__zncc8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":24};
const content = `<path class="r__zncc8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:cocktail" /></template>
