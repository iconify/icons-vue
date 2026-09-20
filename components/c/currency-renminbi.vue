<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f76voxbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f76voxbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-renminbi" /></template>
