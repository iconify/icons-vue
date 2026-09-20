<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4mil5bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="l4mil5bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:format-bold" /></template>
