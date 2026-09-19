<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu9b4b9-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu9b4b9-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:caret-left-fill" /></template>
