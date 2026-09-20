<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9d8-lb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9d8-lb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:google-dataflow" /></template>
