<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6nrz-0-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g6nrz-0-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:hierarchy-13-solid" /></template>
