<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/raun3xbhc.css';
import '../../css/d/dk3eigbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="raun3xbhc"/><path class="dk3eigbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevron-first-bold-duotone" /></template>
