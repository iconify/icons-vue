<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gos3aq1fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gos3aq1fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-x-sharp" /></template>
