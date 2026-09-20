<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw-z017na.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aw-z017na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lantern-fill" /></template>
