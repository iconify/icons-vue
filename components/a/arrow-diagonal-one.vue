<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sli-xybcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sli-xybcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-diagonal-one" /></template>
