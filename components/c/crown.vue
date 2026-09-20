<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbiia3cfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbiia3cfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:crown" /></template>
