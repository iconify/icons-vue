<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex850lb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex850lb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:edit-2-line" /></template>
