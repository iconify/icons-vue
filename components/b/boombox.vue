<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcr_wdbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rcr_wdbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:boombox" /></template>
