<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiq5p1cvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wiq5p1cvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:lifebuoy-filled" /></template>
