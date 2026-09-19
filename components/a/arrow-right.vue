<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evf7b38_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evf7b38_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:arrow-right" /></template>
