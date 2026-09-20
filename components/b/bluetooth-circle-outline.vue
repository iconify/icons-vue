<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiijufoms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wiijufoms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bluetooth-circle-outline" /></template>
