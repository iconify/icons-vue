<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa14hnb-c.css';
import '../../css/b/benlxfbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pa14hnb-c"/><path class="benlxfbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:clipboard-check" /></template>
