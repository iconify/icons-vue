<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pccepgoye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pccepgoye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:4k" /></template>
