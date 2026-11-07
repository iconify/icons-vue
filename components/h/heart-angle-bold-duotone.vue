<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7uoogagy.css';
import '../../css/p/pwof45wsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e7uoogagy"/><path class="pwof45wsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-angle-bold-duotone" /></template>
