<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_snl8-fz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_snl8-fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:history-off" /></template>
