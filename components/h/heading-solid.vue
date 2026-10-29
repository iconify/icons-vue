<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljipl3smr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljipl3smr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:heading-solid" /></template>
