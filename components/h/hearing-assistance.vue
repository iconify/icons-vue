<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_kutkb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":63,"height":64};
const content = `<path class="b_kutkb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:hearing-assistance" /></template>
