<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj7-q5b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj7-q5b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:caret-down-fill" /></template>
