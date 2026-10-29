<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gride0g4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gride0g4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:beef-off" /></template>
