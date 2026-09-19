<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvsc3vbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvsc3vbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:great-wall" /></template>
