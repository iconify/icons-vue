<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud7e4l8zk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud7e4l8zk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:aeroplane" /></template>
