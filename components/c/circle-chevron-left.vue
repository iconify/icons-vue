<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr6lkb-0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr6lkb-0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:circle-chevron-left" /></template>
