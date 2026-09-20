<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9z3f3bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9z3f3bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:grid-one-solid" /></template>
