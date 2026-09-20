<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxomwl-ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxomwl-ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kodi" /></template>
