<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m81es4bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m81es4bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:document-notes" /></template>
