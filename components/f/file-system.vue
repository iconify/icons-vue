<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q80xw6b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q80xw6b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:file-system" /></template>
