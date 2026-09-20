<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsmf72c3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsmf72c3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:etihad-airways" /></template>
