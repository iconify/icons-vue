<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmwoaz3te.css';
import '../../css/m/m6lmdhbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hmwoaz3te"/><path class="m6lmdhbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crane-hook-48-bold" /></template>
