<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj11z5e7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj11z5e7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:credit-card-plus" /></template>
