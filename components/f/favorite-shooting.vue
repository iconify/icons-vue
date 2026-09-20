<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn04et98e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn04et98e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:favorite-shooting" /></template>
