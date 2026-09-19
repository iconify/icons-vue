<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7q-x6bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7q-x6bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-varmblixt" /></template>
