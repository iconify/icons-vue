<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj7raux_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj7raux_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:chevron-right" /></template>
