<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jek51cc3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jek51cc3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:git-commit" /></template>
