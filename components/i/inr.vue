<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9xnn3bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":24};
const content = `<path class="g9xnn3bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:inr" /></template>
