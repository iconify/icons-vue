<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi6oorb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi6oorb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-edit-outline" /></template>
