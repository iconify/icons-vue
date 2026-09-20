<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haue8ibef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="haue8ibef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chili-hot-outline" /></template>
