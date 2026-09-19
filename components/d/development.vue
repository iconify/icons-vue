<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arzliyesj.css';
import '../../css/j/jjrjjnjfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="arzliyesj"/><path class="jjrjjnjfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:development" /></template>
