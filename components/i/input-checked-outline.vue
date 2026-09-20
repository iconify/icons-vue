<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/augh1ex2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="augh1ex2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:input-checked-outline" /></template>
