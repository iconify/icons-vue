<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjtszdm6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjtszdm6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:globe-2-fill" /></template>
