<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu1p-ob8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu1p-ob8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-vertical-3-filled" /></template>
