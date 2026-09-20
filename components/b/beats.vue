<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkt24s-up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkt24s-up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:beats" /></template>
