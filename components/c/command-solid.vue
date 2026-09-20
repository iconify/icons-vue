<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znrnh_b_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="znrnh_b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:command-solid" /></template>
