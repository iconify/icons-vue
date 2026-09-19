<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa5g3utqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xa5g3utqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:calculator" /></template>
