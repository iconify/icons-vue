<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu1k2-bmq.css';
import '../../css/p/pa14hnb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu1k2-bmq"/><path class="pa14hnb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:clipboard-code" /></template>
