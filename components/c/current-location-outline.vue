<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noy8qwcws.css';
import '../../css/v/vvvmsxc8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="noy8qwcws"/><path clip-rule="evenodd" class="vvvmsxc8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:current-location-outline" /></template>
