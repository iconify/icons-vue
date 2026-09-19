<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpo49bc6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpo49bc6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:extension" /></template>
