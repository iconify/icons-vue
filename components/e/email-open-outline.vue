<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6nxtzqqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6nxtzqqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:email-open-outline" /></template>
