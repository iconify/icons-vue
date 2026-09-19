<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mii1j5e-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mii1j5e-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:comment-add-light" /></template>
