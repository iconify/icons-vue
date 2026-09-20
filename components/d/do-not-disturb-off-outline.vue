<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmh-avb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmh-avb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:do-not-disturb-off-outline" /></template>
