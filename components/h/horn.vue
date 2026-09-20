<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp_qd1bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hp_qd1bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:horn" /></template>
