<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw9reep1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw9reep1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:clipboard-data-filled" /></template>
