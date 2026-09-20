<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuk_zebnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cuk_zebnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gps-outline" /></template>
