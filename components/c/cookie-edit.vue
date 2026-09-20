<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr3mles8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr3mles8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cookie-edit" /></template>
