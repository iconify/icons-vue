<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmax83b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmax83b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:bluesky" /></template>
