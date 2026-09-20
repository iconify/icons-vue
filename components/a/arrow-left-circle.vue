<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzs7dac8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzs7dac8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-left-circle" /></template>
