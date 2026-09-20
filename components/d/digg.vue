<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6zb1ub0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6zb1ub0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:digg" /></template>
