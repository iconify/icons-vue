<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg2ixjgdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tg2ixjgdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:connection" /></template>
