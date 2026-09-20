<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3dy-opts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3dy-opts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:logic-gate-xor" /></template>
