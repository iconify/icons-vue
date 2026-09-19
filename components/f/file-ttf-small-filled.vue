<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jueq24bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jueq24bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-ttf-small-filled" /></template>
