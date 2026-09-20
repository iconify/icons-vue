<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgzs6hb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgzs6hb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:add-alert-outline" /></template>
