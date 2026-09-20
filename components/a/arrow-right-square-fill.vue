<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxq523bui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxq523bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:arrow-right-square-fill" /></template>
