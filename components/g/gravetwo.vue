<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5u55gbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="v5u55gbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:gravetwo" /></template>
