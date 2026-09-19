<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrdpt1k-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":416,"height":488};
const content = `<path class="qrdpt1k-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:lovedsgn" /></template>
