<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqun_gwda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqun_gwda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:elevator-solid" /></template>
