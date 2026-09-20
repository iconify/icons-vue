<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t16rme36m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t16rme36m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:briefcase-upload" /></template>
