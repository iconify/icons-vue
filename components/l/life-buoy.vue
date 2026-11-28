<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdwm_7bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdwm_7bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:life-buoy" /></template>
