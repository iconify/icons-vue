<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn4g0qbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn4g0qbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:anchor" /></template>
