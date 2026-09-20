<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew3e48w6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew3e48w6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cactus" /></template>
