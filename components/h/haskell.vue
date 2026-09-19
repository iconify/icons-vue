<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_fi6zbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x_fi6zbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:haskell" /></template>
