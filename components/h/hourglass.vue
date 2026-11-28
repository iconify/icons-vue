<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxa60ulpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxa60ulpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:hourglass" /></template>
