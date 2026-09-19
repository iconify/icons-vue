<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7t4ufb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7t4ufb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:dribbble" /></template>
