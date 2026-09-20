<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzt2xnggt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzt2xnggt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-big-up-short-fill" /></template>
