<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5hqpcc7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j5hqpcc7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:jaguar" /></template>
