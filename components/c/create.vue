<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxwa51bzx.css';
import '../../css/l/l7ztl2cyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxwa51bzx"/><path class="l7ztl2cyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:create" /></template>
