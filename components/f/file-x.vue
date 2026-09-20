<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m275f1bxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m275f1bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-x" /></template>
