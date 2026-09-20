<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cguuphizu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cguuphizu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-braces-bold" /></template>
