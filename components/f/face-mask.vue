<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvjion_2e.css';
import '../../css/z/z8uj590sd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jvjion_2e"/><path class="z8uj590sd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:face-mask" /></template>
