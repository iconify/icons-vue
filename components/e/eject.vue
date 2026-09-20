<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf0d24blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf0d24blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:eject" /></template>
