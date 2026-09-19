<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9eiv2zbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="l9eiv2zbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:lessthan-circle" /></template>
