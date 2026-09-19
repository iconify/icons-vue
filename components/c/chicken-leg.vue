<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh30nu03q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dh30nu03q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chicken-leg" /></template>
