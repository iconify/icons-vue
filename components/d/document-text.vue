<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3q2ambvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3q2ambvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:document-text" /></template>
