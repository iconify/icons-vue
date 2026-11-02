<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o07bh_d7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o07bh_d7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clipboard-minus-line" /></template>
