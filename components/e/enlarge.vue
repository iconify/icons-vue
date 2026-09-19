<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhyc_yb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhyc_yb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:enlarge" /></template>
