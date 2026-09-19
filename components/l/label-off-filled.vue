<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf59cilyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yf59cilyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:label-off-filled" /></template>
