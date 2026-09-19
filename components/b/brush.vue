<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjxhorbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":1026};
const content = `<path class="hjxhorbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:brush" /></template>
