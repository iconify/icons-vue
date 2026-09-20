<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye24n-oam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye24n-oam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:browser-maximize" /></template>
