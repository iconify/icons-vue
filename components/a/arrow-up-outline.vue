<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql_214b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql_214b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:arrow-up-outline" /></template>
