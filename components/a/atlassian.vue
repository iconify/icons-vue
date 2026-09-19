<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc-7fybyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc-7fybyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:atlassian" /></template>
