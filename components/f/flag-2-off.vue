<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvyhydbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvyhydbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flag-2-off" /></template>
