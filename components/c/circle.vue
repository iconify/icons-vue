<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_5yh4fju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="z_5yh4fju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:circle" /></template>
