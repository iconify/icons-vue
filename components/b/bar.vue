<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7cyh0pna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7cyh0pna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:bar" /></template>
