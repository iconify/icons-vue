<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqm7b_roe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jqm7b_roe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bolt-20-bold" /></template>
