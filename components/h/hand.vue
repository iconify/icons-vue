<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asu8thb_w.css';
import '../../css/y/yzgrvsbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="asu8thb_w"/><path class="yzgrvsbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:hand" /></template>
