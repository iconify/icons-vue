<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nslvppb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nslvppb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:corner-down-left" /></template>
