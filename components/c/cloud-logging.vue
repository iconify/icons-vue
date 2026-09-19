<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbfqc9ipi.css';
import '../../css/o/oi7_5_auk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cbfqc9ipi"/><path class="oi7_5_auk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cloud-logging" /></template>
