<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa91rrhan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa91rrhan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:angle-down" /></template>
