<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cssdib97t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="cssdib97t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:bomb-filled" /></template>
