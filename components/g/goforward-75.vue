<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5-3g4bmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="a5-3g4bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:goforward-75" /></template>
