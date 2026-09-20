<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc3ufsb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="sc3ufsb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:list" /></template>
