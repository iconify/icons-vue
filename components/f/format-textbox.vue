<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvyhobc4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvyhobc4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-textbox" /></template>
