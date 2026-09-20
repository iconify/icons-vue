<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-f-jbb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-f-jbb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:elastic-cloud" /></template>
