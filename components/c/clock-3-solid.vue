<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yua8bcbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yua8bcbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:clock-3-solid" /></template>
