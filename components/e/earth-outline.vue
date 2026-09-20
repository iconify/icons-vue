<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv59azbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gv59azbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:earth-outline" /></template>
