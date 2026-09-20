<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icvn2rwbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icvn2rwbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:arrow-downward-fill" /></template>
