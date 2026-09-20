<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsdkdebxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsdkdebxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:cloud-storage" /></template>
