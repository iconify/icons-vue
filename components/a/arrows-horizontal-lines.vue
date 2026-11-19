<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebzczoond.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebzczoond"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:arrows-horizontal-lines" /></template>
