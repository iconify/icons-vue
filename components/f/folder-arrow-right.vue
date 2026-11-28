<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsuuse3db.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsuuse3db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:folder-arrow-right" /></template>
