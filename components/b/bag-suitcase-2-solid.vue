<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2n5-jbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p2n5-jbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bag-suitcase-2-solid" /></template>
