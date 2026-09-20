<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iedg4rbcc.css';
import '../../css/k/kdpqefbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iedg4rbcc"/><path class="kdpqefbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:folder-add-filled" /></template>
