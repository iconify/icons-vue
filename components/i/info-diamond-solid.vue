<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3u4i43bc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3u4i43bc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:info-diamond-solid" /></template>
