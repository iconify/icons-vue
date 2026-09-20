<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6s4wib7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="a6s4wib7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:flower" /></template>
