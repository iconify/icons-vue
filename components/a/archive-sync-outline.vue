<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btsdemx5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btsdemx5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:archive-sync-outline" /></template>
