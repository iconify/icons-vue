<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkknvtmjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lkknvtmjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:diagonal-scroll-1-solid" /></template>
