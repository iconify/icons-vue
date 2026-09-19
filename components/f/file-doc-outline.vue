<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3ex7_fmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3ex7_fmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-doc-outline" /></template>
