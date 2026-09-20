<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpf16_b7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tpf16_b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:lock" /></template>
