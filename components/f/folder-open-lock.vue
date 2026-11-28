<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gch1yna4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gch1yna4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:folder-open-lock" /></template>
