<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sydwlsbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sydwlsbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:boom-barrier-alert" /></template>
