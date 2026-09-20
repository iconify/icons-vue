<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppbprwb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppbprwb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-more-horizontal-fill" /></template>
