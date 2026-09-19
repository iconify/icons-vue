<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk19sqbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk19sqbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:face-frown" /></template>
