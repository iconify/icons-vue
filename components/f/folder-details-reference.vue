<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3vgj9cho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3vgj9cho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-details-reference" /></template>
