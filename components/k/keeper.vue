<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhtgh86zj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhtgh86zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:keeper" /></template>
