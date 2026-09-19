<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqb284kyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":512};
const content = `<path class="hqb284kyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:flag" /></template>
