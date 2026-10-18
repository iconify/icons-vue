<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxzk1vbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxzk1vbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-big-up" /></template>
