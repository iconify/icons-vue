<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx1yiqmcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xx1yiqmcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:info-circle" /></template>
