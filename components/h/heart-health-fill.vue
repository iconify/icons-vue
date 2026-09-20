<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhuown3os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhuown3os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:heart-health-fill" /></template>
