<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obmntvbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obmntvbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:column-line" /></template>
