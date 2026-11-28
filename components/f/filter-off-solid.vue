<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt6hc6pgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt6hc6pgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:filter-off-solid" /></template>
