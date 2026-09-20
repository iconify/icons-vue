<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znrxccwll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znrxccwll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bullet-list" /></template>
