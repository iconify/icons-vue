<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0-3x2b3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0-3x2b3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:file-fill" /></template>
