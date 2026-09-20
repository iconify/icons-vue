<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lul-u6mqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lul-u6mqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:clipboard-check" /></template>
