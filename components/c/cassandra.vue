<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_o620b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q_o620b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:cassandra" /></template>
