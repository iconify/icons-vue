<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slg-pmbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slg-pmbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:archive-remove" /></template>
