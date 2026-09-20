<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrwiemb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrwiemb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-sharp-fill" /></template>
