<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixe1kkbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixe1kkbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-text" /></template>
