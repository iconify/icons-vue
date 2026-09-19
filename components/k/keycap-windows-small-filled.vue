<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aexm2vbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="aexm2vbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-windows-small-filled" /></template>
