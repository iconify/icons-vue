<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz182cbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iz182cbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:kissing-face-fill" /></template>
