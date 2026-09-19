<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3ooak9tu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="z3ooak9tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:buysellads" /></template>
