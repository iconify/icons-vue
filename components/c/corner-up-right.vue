<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yit344byv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yit344byv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:corner-up-right" /></template>
