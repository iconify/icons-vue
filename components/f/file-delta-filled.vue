<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imp9hzbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imp9hzbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:file-delta-filled" /></template>
