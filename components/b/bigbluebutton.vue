<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frwz6gr7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frwz6gr7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:bigbluebutton" /></template>
