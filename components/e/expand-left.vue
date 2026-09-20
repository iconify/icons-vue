<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx-sycb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tx-sycb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:expand-left" /></template>
