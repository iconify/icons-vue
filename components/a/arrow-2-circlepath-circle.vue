<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m25bf8bga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="m25bf8bga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-2-circlepath-circle" /></template>
