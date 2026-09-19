<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to2z3sr5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="to2z3sr5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-left-right" /></template>
