<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksf93nojb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksf93nojb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-shared-line" /></template>
