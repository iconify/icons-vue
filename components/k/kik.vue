<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab6qg3bpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ab6qg3bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kik" /></template>
