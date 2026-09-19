<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxnkqj4fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxnkqj4fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:file" /></template>
