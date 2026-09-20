<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7auwh65h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7auwh65h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dossier-fill" /></template>
