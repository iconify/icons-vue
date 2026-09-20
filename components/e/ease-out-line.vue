<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m40kpbgfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m40kpbgfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ease-out-line" /></template>
