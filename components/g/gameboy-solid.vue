<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2_e2-9vf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o2_e2-9vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:gameboy-solid" /></template>
