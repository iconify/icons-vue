<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v572r_bwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v572r_bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:apple-logo-solid" /></template>
