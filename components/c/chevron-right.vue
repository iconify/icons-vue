<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npaeh2bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npaeh2bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:chevron-right" /></template>
