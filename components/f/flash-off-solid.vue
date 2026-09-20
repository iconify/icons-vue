<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxxpfe0-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cxxpfe0-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:flash-off-solid" /></template>
