<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7m0rrp2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7m0rrp2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:link-2-off" /></template>
