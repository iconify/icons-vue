<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdam21bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdam21bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:focus-fill" /></template>
