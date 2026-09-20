<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml7td3-ud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml7td3-ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:angle-right-filled" /></template>
