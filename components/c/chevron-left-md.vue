<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej6w2kb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej6w2kb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:chevron-left-md" /></template>
