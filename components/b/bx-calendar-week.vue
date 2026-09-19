<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl7z0xbvn.css';
import '../../css/f/fxr_yobjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl7z0xbvn"/><path class="fxr_yobjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-calendar-week" /></template>
