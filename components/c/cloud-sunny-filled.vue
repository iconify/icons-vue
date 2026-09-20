<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww_3snb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ww_3snb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cloud-sunny-filled" /></template>
