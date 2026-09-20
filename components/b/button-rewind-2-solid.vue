<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4x21rbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x4x21rbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:button-rewind-2-solid" /></template>
