<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhket41bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhket41bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:image" /></template>
