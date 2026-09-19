<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk6_l5bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk6_l5bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:checkbox-minus" /></template>
