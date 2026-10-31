<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmx4v4cbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmx4v4cbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:kite-gloss" /></template>
