<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we5l3ab3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="we5l3ab3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:descend" /></template>
