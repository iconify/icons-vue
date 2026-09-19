<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o124r16ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="o124r16ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-turn-right-down" /></template>
