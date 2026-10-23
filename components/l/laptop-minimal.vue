<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2p424b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2p424b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:laptop-minimal" /></template>
