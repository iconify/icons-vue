<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc-a-nvsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc-a-nvsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gnu-bash" /></template>
