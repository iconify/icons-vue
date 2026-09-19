<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpw5bfokz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1536};
const content = `<path class="jpw5bfokz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:cc-discover" /></template>
