<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utxk3l1jo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utxk3l1jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:filter-filled" /></template>
