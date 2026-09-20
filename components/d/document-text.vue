<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2r2wubba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2r2wubba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:document-text" /></template>
