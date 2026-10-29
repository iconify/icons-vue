<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmjpvjb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmjpvjb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:magnet-solid" /></template>
