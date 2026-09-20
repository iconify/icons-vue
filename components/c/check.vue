<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7e_rub6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="e7e_rub6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:check" /></template>
