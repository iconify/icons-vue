<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn93ngxun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn93ngxun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:arrow-repeat" /></template>
