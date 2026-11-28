<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilfdkkb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilfdkkb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:inbox-check" /></template>
