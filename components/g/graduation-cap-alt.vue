<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f54c3mm_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f54c3mm_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:graduation-cap-alt" /></template>
