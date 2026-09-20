<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6j6fiaxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":199};
const content = `<path class="r6j6fiaxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:discord" /></template>
