<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxlo8zbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxlo8zbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:electric-switch" /></template>
