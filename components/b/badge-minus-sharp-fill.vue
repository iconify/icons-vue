<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3htt1wgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t3htt1wgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:badge-minus-sharp-fill" /></template>
