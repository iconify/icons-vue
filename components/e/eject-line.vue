<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfcivp-ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfcivp-ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:eject-line" /></template>
