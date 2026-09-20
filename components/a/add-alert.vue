<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g171l-c8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g171l-c8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:add-alert" /></template>
