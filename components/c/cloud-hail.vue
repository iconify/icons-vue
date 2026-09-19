<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz65g_ywp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz65g_ywp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cloud-hail" /></template>
