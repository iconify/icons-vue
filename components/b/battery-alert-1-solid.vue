<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6ub-1biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s6ub-1biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:battery-alert-1-solid" /></template>
