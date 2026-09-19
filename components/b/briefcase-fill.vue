<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh2am3bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh2am3bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:briefcase-fill" /></template>
