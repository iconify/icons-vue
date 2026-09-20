<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puoatlozo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="puoatlozo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cassette-2-outline" /></template>
