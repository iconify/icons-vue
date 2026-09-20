<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg7ocnbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hg7ocnbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:beer-bottle-and-drink-bottle" /></template>
