<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmzy9jokn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmzy9jokn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:globe" /></template>
