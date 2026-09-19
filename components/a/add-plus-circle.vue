<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_l2a7q7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_l2a7q7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:add-plus-circle" /></template>
