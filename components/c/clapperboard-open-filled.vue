<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdxk5xbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdxk5xbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:clapperboard-open-filled" /></template>
