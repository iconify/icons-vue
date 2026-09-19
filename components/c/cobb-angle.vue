<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a73f9-bto.css';
import '../../css/w/w8e4zs4sx.css';
import '../../css/w/w5hp-fb7h.css';
import '../../css/h/hxu-4ufpy.css';
import '../../css/k/k-319-kjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a73f9-bto"/><path class="w8e4zs4sx"/><path class="w5hp-fb7h"/><path class="hxu-4ufpy"/><path class="k-319-kjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cobb-angle" /></template>
