<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7m83wb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="g7m83wb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:compsition-horizontal-solid" /></template>
