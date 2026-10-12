<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz039ij_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz039ij_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:brick-wall-filled" /></template>
