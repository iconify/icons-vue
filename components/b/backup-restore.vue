<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmy94ub0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmy94ub0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:backup-restore" /></template>
