<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1fqb2bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1fqb2bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:download-outline" /></template>
