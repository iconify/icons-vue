<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oca-jxbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oca-jxbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:currency-bangladeshi" /></template>
