<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cim0r-4qu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cim0r-4qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:edge-computing" /></template>
