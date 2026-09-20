<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oprx6eucf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oprx6eucf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:checkbox-blank" /></template>
