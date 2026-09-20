<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h52p0wbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h52p0wbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:lamp3-filled" /></template>
