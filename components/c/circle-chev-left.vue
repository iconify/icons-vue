<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_6x1nbxh.css';
import '../../css/k/k18y-k1ul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_6x1nbxh"/><path class="k18y-k1ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:circle-chev-left" /></template>
