<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szu0jobmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szu0jobmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:dot-03-m" /></template>
