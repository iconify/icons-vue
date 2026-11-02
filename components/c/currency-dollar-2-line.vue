<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwu5rjrra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwu5rjrra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-dollar-2-line" /></template>
