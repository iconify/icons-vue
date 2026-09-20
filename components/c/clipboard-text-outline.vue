<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goc7o0rte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="goc7o0rte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-text-outline" /></template>
