<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grw1hlb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grw1hlb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bike-basket" /></template>
