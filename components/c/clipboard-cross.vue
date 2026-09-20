<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm9ywsb4k.css';
import '../../css/r/rz27cjbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lm9ywsb4k"/><path class="rz27cjbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:clipboard-cross" /></template>
