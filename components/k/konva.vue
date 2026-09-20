<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmm9ihkeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmm9ihkeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:konva" /></template>
