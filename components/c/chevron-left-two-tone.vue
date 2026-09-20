<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lflyau5pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lflyau5pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevron-left-two-tone" /></template>
