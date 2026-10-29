<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5e3orbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5e3orbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:door-closed-solid" /></template>
