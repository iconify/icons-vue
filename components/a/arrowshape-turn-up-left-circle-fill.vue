<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8r7yvbad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="t8r7yvbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrowshape-turn-up-left-circle-fill" /></template>
