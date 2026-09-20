<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_hzavbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r_hzavbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:browser-key-remix" /></template>
