<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5-yy215v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5-yy215v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flash-red-eye" /></template>
