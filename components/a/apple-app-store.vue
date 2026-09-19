<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro7ekkbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro7ekkbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:apple-app-store" /></template>
