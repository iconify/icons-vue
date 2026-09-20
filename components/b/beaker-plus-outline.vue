<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyw0a_b2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyw0a_b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:beaker-plus-outline" /></template>
