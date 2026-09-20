<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szpxu3l4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="szpxu3l4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:alarm-clock-solid" /></template>
