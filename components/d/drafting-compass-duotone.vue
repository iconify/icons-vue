<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-k7cf_7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary s-k7cf_7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:drafting-compass-duotone" /></template>
