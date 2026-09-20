<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkam1aclb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tkam1aclb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:deepfake-technology-2-remix" /></template>
