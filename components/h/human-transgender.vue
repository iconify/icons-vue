<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx1wcc53c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx1wcc53c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-transgender" /></template>
