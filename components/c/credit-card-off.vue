<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnym_lbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnym_lbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:credit-card-off" /></template>
