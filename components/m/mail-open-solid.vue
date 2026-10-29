<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7kyzlbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7kyzlbcb wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mail-open-solid" /></template>
