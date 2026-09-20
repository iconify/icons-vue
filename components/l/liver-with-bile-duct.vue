<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyojgbk_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gyojgbk_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:liver-with-bile-duct" /></template>
