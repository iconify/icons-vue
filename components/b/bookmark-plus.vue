<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl1cx0q2x.css';
import '../../css/k/krg4_wbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl1cx0q2x wm-k"/><path class="krg4_wbge wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:bookmark-plus" /></template>
