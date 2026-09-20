<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgsy6rdfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgsy6rdfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:download" /></template>
