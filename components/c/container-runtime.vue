<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxlaslbqv.css';
import '../../css/z/zne6o-9jy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oxlaslbqv"/><path class="zne6o-9jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:container-runtime" /></template>
