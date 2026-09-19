<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2ildhqge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="b2ildhqge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:beach-slipper" /></template>
