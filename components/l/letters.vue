<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjb6xsbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjb6xsbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letters" /></template>
