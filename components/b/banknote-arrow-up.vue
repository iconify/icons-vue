<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1x0bac8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1x0bac8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:banknote-arrow-up" /></template>
