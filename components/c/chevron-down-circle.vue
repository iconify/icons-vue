<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwkw019fh.css';
import '../../css/m/mpgu6g9gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="uwkw019fh"/><path clip-rule="evenodd" class="mpgu6g9gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:chevron-down-circle" /></template>
