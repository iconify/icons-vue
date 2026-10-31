<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od5n_tliw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od5n_tliw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-sparkle-corner-fill-round" /></template>
