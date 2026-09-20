<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe09hgbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe09hgbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:giv" /></template>
