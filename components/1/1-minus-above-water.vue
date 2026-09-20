<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs3xk0brh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hs3xk0brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:1-minus-above-water" /></template>
