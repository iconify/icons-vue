<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be4mx6bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be4mx6bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:city-8-filled" /></template>
