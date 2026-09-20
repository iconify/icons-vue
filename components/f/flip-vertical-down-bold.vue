<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdshv-w4n.css';
import '../../css/j/j-cb_fbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdshv-w4n"/><path class="j-cb_fbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:flip-vertical-down-bold" /></template>
