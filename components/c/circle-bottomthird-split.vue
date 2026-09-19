<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyt-ygblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="tyt-ygblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:circle-bottomthird-split" /></template>
