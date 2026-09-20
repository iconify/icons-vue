<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xos-9pjzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xos-9pjzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:download" /></template>
