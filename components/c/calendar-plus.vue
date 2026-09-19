<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgfg_vrnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgfg_vrnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:calendar-plus" /></template>
