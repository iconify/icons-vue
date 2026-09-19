<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek-ptob2h.css';
import '../../css/v/vvuy5gbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<path class="ek-ptob2h"/><path class="vvuy5gbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:eye" /></template>
