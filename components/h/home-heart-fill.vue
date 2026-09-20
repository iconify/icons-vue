<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfwub9bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfwub9bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:home-heart-fill" /></template>
