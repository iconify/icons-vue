<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2_xeebfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2_xeebfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-sync-outline" /></template>
