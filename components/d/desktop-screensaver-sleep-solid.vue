<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m059pvbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m059pvbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:desktop-screensaver-sleep-solid" /></template>
