<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue82kj6gk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue82kj6gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:credit-card-x" /></template>
