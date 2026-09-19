<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o16_wrbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":897,"height":1024};
const content = `<path class="o16_wrbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:clipboard" /></template>
