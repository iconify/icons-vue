<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8cqm23rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p8cqm23rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:calculator-outline" /></template>
