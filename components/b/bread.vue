<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf8-382-y.css';
import '../../css/c/c51exofjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hf8-382-y"/><path class="c51exofjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:bread" /></template>
