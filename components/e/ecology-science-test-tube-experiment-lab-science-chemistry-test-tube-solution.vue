<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu3wysshd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wu3wysshd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ecology-science-test-tube-experiment-lab-science-chemistry-test-tube-solution" /></template>
