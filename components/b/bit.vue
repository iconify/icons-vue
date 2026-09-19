<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq5h7gcxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tq5h7gcxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:bit" /></template>
