<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh4_a5gww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh4_a5gww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-edit-fill" /></template>
