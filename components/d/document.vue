<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccd6l0zmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ccd6l0zmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:document" /></template>
