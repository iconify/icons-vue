<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h38o_z5yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="h38o_z5yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:drop-zone" /></template>
