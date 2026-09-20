<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oolt7f-px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oolt7f-px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:cyborg-2-solid" /></template>
