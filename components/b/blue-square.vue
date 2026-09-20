<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrks0fbpf.css';
import '../../css/t/tbzab391z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="mrks0fbpf"/><path class="tbzab391z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:blue-square" /></template>
