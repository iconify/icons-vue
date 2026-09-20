<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_gotmb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r_gotmb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hexagram-remix" /></template>
