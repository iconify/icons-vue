<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybqfy0iek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybqfy0iek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:application-settings-outline" /></template>
