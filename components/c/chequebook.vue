<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pidlxzb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pidlxzb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chequebook" /></template>
