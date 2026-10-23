<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp6nhjc-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp6nhjc-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:heart-off" /></template>
