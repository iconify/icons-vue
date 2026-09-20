<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u03gbh6os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u03gbh6os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:align-right" /></template>
