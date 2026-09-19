<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx1k7aboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx1k7aboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:achievement" /></template>
