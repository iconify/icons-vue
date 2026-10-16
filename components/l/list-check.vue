<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f75ph4bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f75ph4bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:list-check" /></template>
