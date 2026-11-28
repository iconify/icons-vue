<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxtb7cbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxtb7cbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:archive-check" /></template>
