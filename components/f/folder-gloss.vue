<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhw4n-zri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhw4n-zri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:folder-gloss" /></template>
