<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpkd6tnhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpkd6tnhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:film" /></template>
