<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmdco-tds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmdco-tds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:film-open-check" /></template>
