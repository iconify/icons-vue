<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leqyehr3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="leqyehr3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:heading6" /></template>
