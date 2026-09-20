<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzqgyglra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="tzqgyglra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:flip-vertical-arrow-2" /></template>
