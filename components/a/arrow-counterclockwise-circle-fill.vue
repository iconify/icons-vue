<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvgc2mbbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="uvgc2mbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-counterclockwise-circle-fill" /></template>
