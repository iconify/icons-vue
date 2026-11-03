<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmyx--wgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmyx--wgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:leaf" /></template>
