<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coypw5bme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="coypw5bme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:flutter-logo-solid" /></template>
