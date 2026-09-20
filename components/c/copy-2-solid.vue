<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj5wano6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rj5wano6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:copy-2-solid" /></template>
