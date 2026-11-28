<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o777mrb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="o777mrb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:caret-down-up-light" /></template>
