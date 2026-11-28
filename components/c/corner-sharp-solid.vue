<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcozhwbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcozhwbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:corner-sharp-solid" /></template>
