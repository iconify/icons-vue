<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpbhpqbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":659,"height":727};
const content = `<path class="tpbhpqbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:ampersand" /></template>
