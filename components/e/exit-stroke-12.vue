<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmdbu6bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qmdbu6bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:exit-stroke-12" /></template>
