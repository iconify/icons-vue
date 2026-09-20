<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe-xsrbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pe-xsrbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:glasses-4" /></template>
