<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kddvl9o6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kddvl9o6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:angle-up" /></template>
