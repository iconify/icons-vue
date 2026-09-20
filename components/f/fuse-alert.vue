<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_rhs3pvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_rhs3pvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fuse-alert" /></template>
