<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrldg9bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrldg9bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:arrow-right-thick" /></template>
