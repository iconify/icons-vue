<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k10e7hshi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k10e7hshi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-export" /></template>
