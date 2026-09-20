<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezeah_box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezeah_box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:design-tool-magic-wand" /></template>
