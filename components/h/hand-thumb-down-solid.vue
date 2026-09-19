<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/febe2bc5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="febe2bc5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:hand-thumb-down-solid" /></template>
