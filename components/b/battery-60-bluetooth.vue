<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugiwfub4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugiwfub4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-60-bluetooth" /></template>
