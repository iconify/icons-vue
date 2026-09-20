<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1wpx7blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t1wpx7blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:circle-clock-solid" /></template>
