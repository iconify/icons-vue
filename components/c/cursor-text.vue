<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge6fk3bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ge6fk3bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cursor-text" /></template>
