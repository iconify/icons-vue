<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whrh0-uol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whrh0-uol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:equal-double" /></template>
