<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq057jbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq057jbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:arrow-circle-down" /></template>
