<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr1oq5bin.css';
import '../../css/u/uybrlibii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr1oq5bin"/><path class="uybrlibii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-layer-minus" /></template>
