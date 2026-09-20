<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/povo_89as.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="povo_89as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-tinder" /></template>
