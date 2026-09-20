<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgbnv1b-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgbnv1b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:gog" /></template>
