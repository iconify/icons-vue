<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcuxe76bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcuxe76bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:google-play" /></template>
