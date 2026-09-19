<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rphqfaj4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rphqfaj4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:kitchen" /></template>
