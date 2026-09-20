<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jco9mbcel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jco9mbcel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:credit-card-edit" /></template>
