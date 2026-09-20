<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cizcas08r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cizcas08r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-fact-line" /></template>
