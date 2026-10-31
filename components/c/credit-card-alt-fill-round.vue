<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0ln88bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0ln88bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-alt-fill-round" /></template>
