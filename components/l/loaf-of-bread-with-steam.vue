<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzbc27bpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tzbc27bpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:loaf-of-bread-with-steam" /></template>
