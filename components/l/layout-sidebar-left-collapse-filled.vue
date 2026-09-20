<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prn9v0brd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prn9v0brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-sidebar-left-collapse-filled" /></template>
