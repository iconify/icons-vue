<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/god23jbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="god23jbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chevron-down-double" /></template>
