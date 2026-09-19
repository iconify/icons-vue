<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzbumwr0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xzbumwr0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-right-5-circle-fill" /></template>
