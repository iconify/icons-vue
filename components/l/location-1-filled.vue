<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjvb-7nsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjvb-7nsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:location-1-filled" /></template>
