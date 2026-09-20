<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgiqbzbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgiqbzbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:left-up-fill" /></template>
