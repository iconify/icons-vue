<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnsxrmu_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tnsxrmu_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:leaf-remix" /></template>
