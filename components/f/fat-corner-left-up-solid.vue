<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd_-_xc8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pd_-_xc8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-corner-left-up-solid" /></template>
