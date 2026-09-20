<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v194byb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v194byb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:droplet-with-shine" /></template>
