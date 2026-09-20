<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgkusyvhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgkusyvhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:arrow-trending" /></template>
