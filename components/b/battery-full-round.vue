<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tly34rbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tly34rbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-full-round" /></template>
