<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6mgy9awu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":582,"height":1000};
const content = `<path class="r6mgy9awu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:lock" /></template>
