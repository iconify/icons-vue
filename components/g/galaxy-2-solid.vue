<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teur4xb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="teur4xb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:galaxy-2-solid" /></template>
