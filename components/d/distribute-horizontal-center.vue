<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyto10bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyto10bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:distribute-horizontal-center" /></template>
