<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whvybwb6j.css';
import '../../css/d/d0psnynrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="whvybwb6j"/><path class="d0psnynrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:columns-3-cog-filled" /></template>
