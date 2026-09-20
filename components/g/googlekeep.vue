<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue0oukb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue0oukb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:googlekeep" /></template>
