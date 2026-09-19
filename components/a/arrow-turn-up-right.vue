<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oeaogk41p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="oeaogk41p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-turn-up-right" /></template>
