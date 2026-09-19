<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjfreibgp.css';
import '../../css/c/ca5ecz53l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rjfreibgp"/><path class="ca5ecz53l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:fit-to-width" /></template>
