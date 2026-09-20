<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpi01cc4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="kpi01cc4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:battery-one-quarter-f" /></template>
