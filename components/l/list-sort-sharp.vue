<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gga2dabrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gga2dabrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-sort-sharp" /></template>
