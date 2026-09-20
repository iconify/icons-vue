<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg3c0pb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kg3c0pb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-down-left-24" /></template>
