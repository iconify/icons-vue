<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjbyqm_dz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjbyqm_dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:anchor-fill" /></template>
