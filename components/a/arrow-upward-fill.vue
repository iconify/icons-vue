<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/engovybkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="engovybkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:arrow-upward-fill" /></template>
