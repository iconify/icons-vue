<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjg6l7blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjg6l7blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:activity-solid" /></template>
