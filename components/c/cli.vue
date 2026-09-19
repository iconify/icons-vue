<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0h3ws6gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0h3ws6gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:cli" /></template>
