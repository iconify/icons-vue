<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peh9kwb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="peh9kwb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:equal" /></template>
