<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlsj3jbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlsj3jbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:adjustments-plus" /></template>
