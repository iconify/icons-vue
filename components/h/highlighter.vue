<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vva995_fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-0.5,"top":-1};
const content = `<path class="vva995_fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:highlighter" /></template>
