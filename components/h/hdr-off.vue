<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se7i_-b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se7i_-b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hdr-off" /></template>
