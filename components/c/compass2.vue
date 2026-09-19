<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-rbzqbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i-rbzqbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:compass2" /></template>
