<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scrsn1bbj.css';
import '../../css/t/tsynbibhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="scrsn1bbj"/><path class="tsynbibhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:food-drink-fruit-cherry" /></template>
