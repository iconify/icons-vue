<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zicn750et.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zicn750et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:expand" /></template>
