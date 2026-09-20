<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf-ely3-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf-ely3-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-squares-duotone" /></template>
