<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhfgegfss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhfgegfss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chevron-up-s" /></template>
