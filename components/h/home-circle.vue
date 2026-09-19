<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o79d83b5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o79d83b5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:home-circle" /></template>
