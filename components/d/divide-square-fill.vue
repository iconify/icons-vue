<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8m2hz8lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8m2hz8lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:divide-square-fill" /></template>
