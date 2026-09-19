<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/naj-5-b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="naj-5-b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:dots-circle-horizontal" /></template>
