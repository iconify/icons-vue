<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x78bggbaj.css';
import '../../css/u/um2797y-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x78bggbaj"/><path class="um2797y-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-scan-filled" /></template>
