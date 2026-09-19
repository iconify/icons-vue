<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf8ha8baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf8ha8baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:hue-sync-strip" /></template>
