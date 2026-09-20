<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujv856v3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujv856v3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:call-end" /></template>
