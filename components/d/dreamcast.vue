<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp64d8skd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sp64d8skd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dreamcast" /></template>
