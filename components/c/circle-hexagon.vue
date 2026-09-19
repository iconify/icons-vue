<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4yh9sqql.css';
import '../../css/a/aps6ewwol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b x4yh9sqql"/><path class="aps6ewwol b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:circle-hexagon" /></template>
