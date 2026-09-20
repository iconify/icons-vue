<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfdhb-19z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfdhb-19z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:arrow-thick-right-bottom-corner-3" /></template>
