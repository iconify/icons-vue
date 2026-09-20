<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmgz4fbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmgz4fbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:arrow-left-outline" /></template>
