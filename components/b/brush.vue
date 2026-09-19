<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-qoz2f0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r-qoz2f0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:brush" /></template>
