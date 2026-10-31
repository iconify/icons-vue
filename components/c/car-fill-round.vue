<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7-wf6bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7-wf6bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:car-fill-round" /></template>
