<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz1b3xbnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz1b3xbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-left-2-fill" /></template>
