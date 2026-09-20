<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcb-l8b2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcb-l8b2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alert-remove-outline" /></template>
