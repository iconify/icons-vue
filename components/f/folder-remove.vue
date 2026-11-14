<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt-cg6y3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt-cg6y3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-remove" /></template>
