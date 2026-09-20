<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtt7l7bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtt7l7bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:angle-double-up" /></template>
