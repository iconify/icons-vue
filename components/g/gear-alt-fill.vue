<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt_ud7bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="lt_ud7bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:gear-alt-fill" /></template>
