<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpopvy77i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpopvy77i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-fill-round" /></template>
