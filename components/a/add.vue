<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu4mllbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu4mllbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:add" /></template>
