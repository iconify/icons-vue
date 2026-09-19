<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx8s2qyca.css';
import '../../css/x/x9g2eubxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yx8s2qyca"/><path class="x9g2eubxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-player" /></template>
