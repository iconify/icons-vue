<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xznamb27i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xznamb27i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kibana" /></template>
