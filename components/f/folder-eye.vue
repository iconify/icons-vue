<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om8bjvbqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om8bjvbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-eye" /></template>
