<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsas4b2vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsas4b2vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:clock-12" /></template>
