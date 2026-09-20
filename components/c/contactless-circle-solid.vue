<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkez5lb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkez5lb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:contactless-circle-solid" /></template>
