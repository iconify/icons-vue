<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptpts-iao.css';
import '../../css/k/kjhhmyhjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ptpts-iao"/><path class="kjhhmyhjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-text-input-area-2" /></template>
