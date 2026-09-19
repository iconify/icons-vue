<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp0mvq0pn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp0mvq0pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:flows" /></template>
