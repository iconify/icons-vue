<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpcg-pb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="tpcg-pb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:app-fill" /></template>
