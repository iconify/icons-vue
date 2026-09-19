<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xao59bcgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xao59bcgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:bell-notification" /></template>
