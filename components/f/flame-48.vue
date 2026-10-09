<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqe_kssen.css';
import '../../css/j/jl4dq47bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pqe_kssen"/><path class="jl4dq47bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flame-48" /></template>
