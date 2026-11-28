<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htktd2baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htktd2baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:castle-star" /></template>
