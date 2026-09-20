<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6e4g6mrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s6e4g6mrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ethereum-circle-solid" /></template>
