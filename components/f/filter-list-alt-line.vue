<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imojjfb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imojjfb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:filter-list-alt-line" /></template>
