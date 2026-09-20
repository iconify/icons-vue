<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx3h3z0iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx3h3z0iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:cloud-storage-outline" /></template>
