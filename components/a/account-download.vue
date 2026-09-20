<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3urfac0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3urfac0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-download" /></template>
