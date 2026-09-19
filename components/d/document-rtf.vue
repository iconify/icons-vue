<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld7du4pgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld7du4pgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:document-rtf" /></template>
