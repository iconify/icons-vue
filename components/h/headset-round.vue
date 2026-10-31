<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcs2ixboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcs2ixboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:headset-round" /></template>
