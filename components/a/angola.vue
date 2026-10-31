<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci23lkb2t.css';
import '../../css/q/qfc3cc3so.css';
import '../../css/z/zvg42bbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="ci23lkb2t"/><path class="qfc3cc3so"/><path class="zvg42bbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:angola" /></template>
