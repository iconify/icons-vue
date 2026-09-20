<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu-vxgbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu-vxgbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:bow-tie" /></template>
