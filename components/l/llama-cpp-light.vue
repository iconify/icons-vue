<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7r4hpltc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f7r4hpltc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:llama-cpp-light" /></template>
