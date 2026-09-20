<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqpkglsgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqpkglsgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:border-top" /></template>
