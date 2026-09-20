<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zovupsb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zovupsb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heart-circle-solid" /></template>
