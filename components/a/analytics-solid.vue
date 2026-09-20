<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdn7ccb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdn7ccb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:analytics-solid" /></template>
