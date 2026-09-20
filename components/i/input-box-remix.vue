<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8bnu1bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l8bnu1bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:input-box-remix" /></template>
