<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvrw6qbih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvrw6qbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:basket" /></template>
