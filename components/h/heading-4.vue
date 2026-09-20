<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft8hti5fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft8hti5fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:heading-4" /></template>
