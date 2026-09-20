<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qav90nb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qav90nb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-exclamation" /></template>
