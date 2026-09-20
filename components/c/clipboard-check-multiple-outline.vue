<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/royomp97n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="royomp97n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-check-multiple-outline" /></template>
