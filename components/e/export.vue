<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr89lk6nk.css';
import '../../css/m/mli_10bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="zr89lk6nk"/><path class="mli_10bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:export" /></template>
