<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqn3_72mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqn3_72mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-left-down" /></template>
