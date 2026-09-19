<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_7cduu4i.css';
import '../../css/x/xu6tp6cqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_7cduu4i"/><path class="xu6tp6cqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:lungs" /></template>
