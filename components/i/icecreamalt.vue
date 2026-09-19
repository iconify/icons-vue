<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo9isi4jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":1024};
const content = `<path class="jo9isi4jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:icecreamalt" /></template>
