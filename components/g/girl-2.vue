<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkpfgi2gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vkpfgi2gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:girl-2" /></template>
