<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o50glqbqr.css';
import '../../css/z/zglupmbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o50glqbqr"/><path class="zglupmbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:assemblyai" /></template>
