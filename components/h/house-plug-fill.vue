<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruaav7bvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruaav7bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:house-plug-fill" /></template>
