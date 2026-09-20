<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekghdyv4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekghdyv4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:file-download-duotone" /></template>
