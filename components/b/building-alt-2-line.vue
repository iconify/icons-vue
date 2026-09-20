<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukh3251yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukh3251yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:building-alt-2-line" /></template>
