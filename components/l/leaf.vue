<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udi-aab5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udi-aab5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:leaf" /></template>
