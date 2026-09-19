<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9j6r52xi.css';
import '../../css/c/c-cig4bdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f9j6r52xi"/><path class="c-cig4bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-loop-left-filled" /></template>
