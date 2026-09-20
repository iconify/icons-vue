<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqol3ybqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqol3ybqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:favorite-settings" /></template>
