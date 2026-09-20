<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwackbbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwackbbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:label-alt-multiple" /></template>
