<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwjqdwbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwjqdwbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:file-solid" /></template>
