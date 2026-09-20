<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my_i5-smp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my_i5-smp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:italics" /></template>
