<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfvamcckl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfvamcckl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:highlight-1-filled" /></template>
