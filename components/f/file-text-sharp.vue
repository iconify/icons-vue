<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlas83qsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlas83qsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-text-sharp" /></template>
