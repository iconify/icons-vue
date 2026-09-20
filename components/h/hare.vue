<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm9m8zbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm9m8zbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hare" /></template>
