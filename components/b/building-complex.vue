<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o981pybxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o981pybxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:building-complex" /></template>
