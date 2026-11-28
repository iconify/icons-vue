<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szr2kr31a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szr2kr31a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:briefcase-x" /></template>
