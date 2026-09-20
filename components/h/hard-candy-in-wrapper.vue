<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mixc26bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mixc26bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:hard-candy-in-wrapper" /></template>
