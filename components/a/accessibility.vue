<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nugogpbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nugogpbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:accessibility" /></template>
