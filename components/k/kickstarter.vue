<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1em5i3_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="w1em5i3_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:kickstarter" /></template>
