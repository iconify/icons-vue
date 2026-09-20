<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfp4okqko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pfp4okqko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:arrow-reload-horizontal-2-solid" /></template>
