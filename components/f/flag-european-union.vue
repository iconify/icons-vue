<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/codjm1acu.css';
import '../../css/h/hjc6v1b6h.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="codjm1acu"/><path class="hjc6v1b6h"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-european-union" /></template>
