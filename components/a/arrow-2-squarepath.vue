<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r22r-9bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="r22r-9bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-2-squarepath" /></template>
