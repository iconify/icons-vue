<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioh76cbbc.css';
import '../../css/k/ksr3op_7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ioh76cbbc"/><path class="ksr3op_7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-loop-right" /></template>
