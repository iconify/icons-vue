<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jow4trbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jow4trbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:credit-card-fill" /></template>
