<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds9m95fda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds9m95fda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-bottom-filled" /></template>
